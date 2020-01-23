critic-lr: 0.0003
train-step-num: 1
imitation-weight: 0.5
record-start-size: 10000.0
filter-torque: False
loss-output-bound-coeff: 0.0
expert-num: 4
render-eval: False
max-path-num: 20
critic-weight-decay: 1e-06
joint-interpolation: True
critic-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 2.0
HLC-frequency: 25
n-step: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-lr: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-activation-fn: ['relu', 'relu', 'None']
epoch-step-num: 5000000
actor-layer-size: [256, 256]
reward-scale: 0.1
filter-action: True
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
Physics-frequency: 1000
replay-ratio: 1
task-weight: 0.5
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
critic-layer-size: [256, 256]
loss-output-diff-coeff: 0
max-step-num: 2500000000
state-dim: 23
prioritized-exp-replay: True
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-freq: 1.667
env-id: HumanoidBalanceFilter-v0
replay-start-size: 10000
dsr-gait-period: 0.6
loss-entropy-coeff: 0.0
expert-index: None
critic-l2-reg: 0.0003
gating-index: None
rollout-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
replay-buffer-size: 1000000
max-train-time: 10
bullet-default-PD: False
squash-action: True
tau: 0.001
total-step-num: 2500000000
actor-l2-reg: 0.0003
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
gating-layer-size: [32, 32]
LLC-frequency: 500
gamma: 0.955
max-test-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
test-num: 4
epoch-num: 500
action-dim: 12
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
