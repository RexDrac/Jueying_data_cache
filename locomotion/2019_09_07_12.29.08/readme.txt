actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
rollout-step-num: 1
replay-ratio: 1
gating-index: None
total-step-num: 2500000000
task-weight: 0.5
epoch-step-num: 5000000
max-step-num: 2500000000
actor-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
env-id: HumanoidBalanceFilter-v0
max-test-time: 10
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
interpolation: False
loss-output-diff-coeff: 0
bullet-default-PD: False
critic-lr: 0.0003
max-path-num: 20
loss-entropy-coeff: 0.0
replay-buffer-size: 1000000
filter-torque: False
critic-weight-decay: 1e-06
gating-layer-size: [32, 32]
critic-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
reward-scale: 0.1
dsr-gait-period: 0.6
max-train-time: 10
epoch-num: 500
actor-weight-decay: 1e-06
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
replay-start-size: 10000
imitation-weight: 0.5
expert-index: None
squash-action: True
record-start-size: 10000.0
Physics-frequency: 1000
joint-interpolation: True
actor-l2-reg: 0.0003
dsr-gait-freq: 1.667
loss-output-bound-coeff: 0.0
LLC-frequency: 500
gating-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'n_atoms': 51, 'v_min': -10}
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-layer-size: [256, 256]
render-eval: False
test-num: 4
HLC-frequency: 25
loss-output-smooth-coeff: 0.5
filter-action: True
train-step-num: 1
state-dim: 23
prioritized-exp-replay: True
actor-lr: 0.0003
gamma: 0.955
critic-l2-reg: 0.0003
expert-num: 4
max-episode-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
tau: 0.001
critic-layer-size: [256, 256]
n-step: 1
action-dim: 12
