render-eval: False
critic-l2-reg: 0.0003
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
loss-output-diff-coeff: 0
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
gating-index: None
actor-lr: 0.0003
bullet-default-PD: False
action-dim: 12
reward-scale: 0.1
prioritized-exp-replay: True
max-episode-num: 5000000
squash-action: True
test-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
epoch-step-num: 5000000
interpolation: False
imitation-weight: 0.5
filter-action: True
expert-num: 4
gating-layer-size: [32, 32]
epoch-num: 500
max-path-num: 20
batch-size: 128
tau: 0.001
dsr-gait-period: 0.6
actor-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
filter-torque: False
actor-l2-reg: 0.0003
expert-index: None
rollout-step-num: 1
max-path-step: 5000
loss-entropy-coeff: 0.0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gamma: 0.955
critic-layer-size: [256, 256]
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
loss-output-bound-coeff: 0.0
record-start-size: 10000.0
max-test-time: 10
gating-activation-fn: ['relu', 'relu', 'None']
replay-buffer-size: 1000000
critic-weight-decay: 1e-06
HLC-frequency: 25
max-train-time: 10
dsr-gait-freq: 1.667
train-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
total-step-num: 2500000000
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
task-weight: 0.5
LLC-frequency: 500
critic-lr: 0.0003
joint-interpolation: True
state-dim: 23
max-step-num: 2500000000
n-step: 1
replay-ratio: 1
replay-start-size: 10000
